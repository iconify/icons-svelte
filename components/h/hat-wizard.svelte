<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgi4_yeue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wgi4_yeue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hat-wizard" {...props}></Icon>
