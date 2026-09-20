<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_yapab2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_yapab2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gold-bars-bold" {...props}></Icon>
