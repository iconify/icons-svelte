<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxdr6dbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="mxdr6dbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:output" {...props}></Icon>
