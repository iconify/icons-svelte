<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaxm-tbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jaxm-tbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-square-30-line" {...props}></Icon>
