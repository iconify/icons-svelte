<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvr2orbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zvr2orbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ppt" {...props}></Icon>
