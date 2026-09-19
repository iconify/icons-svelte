<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g48a6w0ps.css';
import '../../css/x/xwy_3hbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g48a6w0ps"/><path class="xwy_3hbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-thunderstorm" {...props}></Icon>
