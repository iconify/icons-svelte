<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho_1kcwhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ho_1kcwhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:recording" {...props}></Icon>
