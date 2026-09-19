<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lewgvx2df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lewgvx2df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-button-alt-filled" {...props}></Icon>
