<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvy4vpqps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvy4vpqps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:pen" {...props}></Icon>
