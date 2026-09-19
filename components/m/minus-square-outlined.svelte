<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy9coyx8u.css';
import '../../css/g/gc8-4tb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gy9coyx8u"/><path class="gc8-4tb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:minus-square-outlined" {...props}></Icon>
