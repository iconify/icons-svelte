<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvtboac2u.css';
import '../../css/m/m23pcacuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvtboac2u"/><path class="m23pcacuc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:datasette-dark" {...props}></Icon>
