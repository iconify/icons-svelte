<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r--l4krnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="r--l4krnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-link-create-hyperlink-link-make-unlink" {...props}></Icon>
