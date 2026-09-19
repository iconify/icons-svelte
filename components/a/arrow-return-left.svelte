<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q00d-m2wl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q00d-m2wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-return-left" {...props}></Icon>
