<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqzvsjbqs.css';
import '../../css/p/p1lsw9_1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqzvsjbqs"/><path class="p1lsw9_1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bludit" {...props}></Icon>
