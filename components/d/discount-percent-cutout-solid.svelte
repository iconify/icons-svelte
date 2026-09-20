<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0kp7lb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v0kp7lb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:discount-percent-cutout-solid" {...props}></Icon>
