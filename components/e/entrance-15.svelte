<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6qtzmbeo.css';
import '../../css/y/ybtqz23gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m6qtzmbeo"/><path class="ybtqz23gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:entrance-15" {...props}></Icon>
