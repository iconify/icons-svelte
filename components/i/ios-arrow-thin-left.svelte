<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgtb81bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hgtb81bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-thin-left" {...props}></Icon>
