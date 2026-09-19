<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmdssxr9w.css';
import '../../css/d/d709sgber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmdssxr9w"/><path class="d709sgber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-beaker" {...props}></Icon>
