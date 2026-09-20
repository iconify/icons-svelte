<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7e1jibgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j7e1jibgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:biking-solid" {...props}></Icon>
