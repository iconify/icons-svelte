<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2sacr10w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s2sacr10w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:digital-ocean" {...props}></Icon>
