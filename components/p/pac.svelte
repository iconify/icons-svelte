<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xin55vtfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xin55vtfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pac" {...props}></Icon>
