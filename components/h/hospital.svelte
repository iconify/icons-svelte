<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff6qa3bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ff6qa3bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hospital" {...props}></Icon>
