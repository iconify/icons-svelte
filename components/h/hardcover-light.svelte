<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epx4oac-v.css';
import '../../css/k/k4v90z5go.css';
import '../../css/h/hv1gm7eyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epx4oac-v"/><path class="k4v90z5go"/><path class="hv1gm7eyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hardcover-light" {...props}></Icon>
