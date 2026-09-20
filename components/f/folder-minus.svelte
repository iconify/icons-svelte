<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn88f4bao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="xn88f4bao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:folder-minus" {...props}></Icon>
