<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru6zld64q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru6zld64q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-wipe-down-filled" {...props}></Icon>
