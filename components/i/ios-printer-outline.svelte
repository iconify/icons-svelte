<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojqan9b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojqan9b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-printer-outline" {...props}></Icon>
