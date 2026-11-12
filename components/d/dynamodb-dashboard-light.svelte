<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3k1g3byx.css';
import '../../css/z/zl5x12lyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t3k1g3byx"/><path class="zl5x12lyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynamodb-dashboard-light" {...props}></Icon>
