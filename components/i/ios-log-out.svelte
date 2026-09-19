<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejh5nmbuc.css';
import '../../css/d/d7j4pp_vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ejh5nmbuc"/><path class="d7j4pp_vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-log-out" {...props}></Icon>
