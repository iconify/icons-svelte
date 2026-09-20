<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_c6c0bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c_c6c0bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:circle-stroked" {...props}></Icon>
