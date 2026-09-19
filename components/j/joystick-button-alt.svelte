<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y88ha-yho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y88ha-yho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:joystick-button-alt" {...props}></Icon>
