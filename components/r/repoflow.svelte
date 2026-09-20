<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/faekp9bkh.css';
import '../../css/r/ry8otvb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="faekp9bkh"/><path class="ry8otvb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:repoflow" {...props}></Icon>
