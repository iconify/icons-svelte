<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs__h_6vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hs__h_6vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ntbc" {...props}></Icon>
