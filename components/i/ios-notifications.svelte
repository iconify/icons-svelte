<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu3wmc3lc.css';
import '../../css/k/k6ez9jbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zu3wmc3lc"/><path class="k6ez9jbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-notifications" {...props}></Icon>
