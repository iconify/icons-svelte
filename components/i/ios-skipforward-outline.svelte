<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc-22ebky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc-22ebky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-skipforward-outline" {...props}></Icon>
