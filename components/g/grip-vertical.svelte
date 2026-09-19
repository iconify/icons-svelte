<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvc7i_bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvc7i_bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:grip-vertical" {...props}></Icon>
