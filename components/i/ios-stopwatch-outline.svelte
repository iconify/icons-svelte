<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt3z6yb7q.css';
import '../../css/m/m635pzbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bt3z6yb7q"/><path class="m635pzbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-stopwatch-outline" {...props}></Icon>
