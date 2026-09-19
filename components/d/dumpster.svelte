<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxgit7ceq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rxgit7ceq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dumpster" {...props}></Icon>
