<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joucdub-z.css';
import '../../css/h/hwp54b9_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="joucdub-z"/><path class="hwp54b9_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:audio-muted-outlined" {...props}></Icon>
