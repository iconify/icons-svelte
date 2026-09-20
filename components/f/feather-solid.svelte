<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi0ta7b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hi0ta7b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:feather-solid" {...props}></Icon>
