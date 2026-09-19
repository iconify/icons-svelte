<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jajh-lbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jajh-lbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:poly" {...props}></Icon>
