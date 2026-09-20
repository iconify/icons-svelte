<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4tw2iwcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4tw2iwcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gravatar" {...props}></Icon>
