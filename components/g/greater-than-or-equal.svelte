<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vma9j-bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vma9j-bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:greater-than-or-equal" {...props}></Icon>
