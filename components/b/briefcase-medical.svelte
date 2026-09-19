<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn36-5bgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xn36-5bgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:briefcase-medical" {...props}></Icon>
