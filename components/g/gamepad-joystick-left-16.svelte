<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g28rmbcxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g28rmbcxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:gamepad-joystick-left-16" {...props}></Icon>
