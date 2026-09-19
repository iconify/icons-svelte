<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qozmdccui.css';
import '../../css/z/zvp6zsbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qozmdccui"/><path class="zvp6zsbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:finger-swipe-down" {...props}></Icon>
