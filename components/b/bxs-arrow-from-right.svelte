<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7o2scm7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7o2scm7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-arrow-from-right" {...props}></Icon>
