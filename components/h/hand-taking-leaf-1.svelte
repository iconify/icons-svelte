<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhl0h1bhb.css';
import '../../css/j/jcs27cipf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhl0h1bhb"/><path class="jcs27cipf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:hand-taking-leaf-1" {...props}></Icon>
