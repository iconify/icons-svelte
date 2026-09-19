<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcrw8i3lq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcrw8i3lq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cloud-done" {...props}></Icon>
