<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql7ror-gd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ql7ror-gd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-stop" {...props}></Icon>
