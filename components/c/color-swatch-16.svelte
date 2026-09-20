<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab9e4v7oo.css';
import '../../css/w/wvyfc4bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ab9e4v7oo"/><path clip-rule="evenodd" class="wvyfc4bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:color-swatch-16" {...props}></Icon>
