<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji9ha2b1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ji9ha2b1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-compass" {...props}></Icon>
