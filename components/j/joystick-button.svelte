<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdh4qvbdd.css';
import '../../css/z/zb9ioj-fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdh4qvbdd"/><path class="zb9ioj-fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-button" {...props}></Icon>
