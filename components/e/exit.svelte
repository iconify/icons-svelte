<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aatdglbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aatdglbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:exit" {...props}></Icon>
