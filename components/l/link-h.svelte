<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-yrc1biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-yrc1biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:link-h" {...props}></Icon>
