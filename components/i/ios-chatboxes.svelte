<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgj2dwchq.css';
import '../../css/a/airmpdfkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qgj2dwchq"/><path class="airmpdfkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-chatboxes" {...props}></Icon>
