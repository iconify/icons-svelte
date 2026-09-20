<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv7mem_ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv7mem_ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:check-circle-filled" {...props}></Icon>
