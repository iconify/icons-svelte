<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8m-_-bks.css';
import '../../css/j/juspnkb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="a8m-_-bks"/><path class="juspnkb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:rest-outline" {...props}></Icon>
