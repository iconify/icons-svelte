<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hr_1osbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":432};
const content = `<path class="hr_1osbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-strikethrough-s" {...props}></Icon>
