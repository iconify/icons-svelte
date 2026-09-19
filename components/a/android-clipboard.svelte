<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmkmzzb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kmkmzzb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-clipboard" {...props}></Icon>
