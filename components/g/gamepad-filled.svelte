<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjzikpbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjzikpbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gamepad-filled" {...props}></Icon>
