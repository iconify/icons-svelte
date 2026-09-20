<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf-c6_b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pf-c6_b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:density-s-filled" {...props}></Icon>
