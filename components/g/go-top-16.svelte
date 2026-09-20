<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znnm_ubqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="znnm_ubqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:go-top-16" {...props}></Icon>
