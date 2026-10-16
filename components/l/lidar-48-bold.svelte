<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9awjfzyj.css';
import '../../css/f/f7niv6bbj.css';
import '../../css/f/figjuehvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l9awjfzyj"/><path class="f7niv6bbj"/><path class="figjuehvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lidar-48-bold" {...props}></Icon>
