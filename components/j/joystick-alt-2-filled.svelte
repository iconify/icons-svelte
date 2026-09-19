<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj2kbxtoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oj2kbxtoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-alt-2-filled" {...props}></Icon>
