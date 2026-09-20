<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lczo6ys_s.css';
import '../../css/c/cxrrxpb0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lczo6ys_s"/><path class="cxrrxpb0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:mathematics-display-default" {...props}></Icon>
