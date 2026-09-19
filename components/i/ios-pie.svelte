<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdokhcczj.css';
import '../../css/o/ohy4x1bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pdokhcczj"/><path class="ohy4x1bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-pie" {...props}></Icon>
