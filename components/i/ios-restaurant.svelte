<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkc2bcb8o.css';
import '../../css/o/oevl03-th.css';
import '../../css/t/tv3azrqgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pkc2bcb8o"/><path class="oevl03-th"/><path class="tv3azrqgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-restaurant" {...props}></Icon>
