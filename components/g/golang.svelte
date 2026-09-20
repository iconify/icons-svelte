<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycy_tv9yp.css';
import '../../css/n/n5h7sdi6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="ycy_tv9yp"/><path class="n5h7sdi6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:golang" {...props}></Icon>
