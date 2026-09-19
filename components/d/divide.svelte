<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk8_5zbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="uk8_5zbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:divide" {...props}></Icon>
