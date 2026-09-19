<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq2m00b2g.css';
import '../../css/a/a6rvn_b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq2m00b2g"/><path class="a6rvn_b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-copy-alt" {...props}></Icon>
