<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xozmq__7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xozmq__7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-button-filled" {...props}></Icon>
