<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv7pv6b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qv7pv6b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:aircraft-take-off" {...props}></Icon>
