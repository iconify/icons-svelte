<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7iv0c6ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l7iv0c6ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:corner-up-left-fill" {...props}></Icon>
