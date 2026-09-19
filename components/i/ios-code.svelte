<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt5z90bty.css';
import '../../css/o/op7udfbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt5z90bty"/><path class="op7udfbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-code" {...props}></Icon>
