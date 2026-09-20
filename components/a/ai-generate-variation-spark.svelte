<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a42hircgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="a42hircgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:ai-generate-variation-spark" {...props}></Icon>
