<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asux9-iud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="asux9-iud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:css" {...props}></Icon>
