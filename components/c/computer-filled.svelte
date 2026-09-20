<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2ooj9bpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="b2ooj9bpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:computer-filled" {...props}></Icon>
