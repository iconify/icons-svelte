<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hadh28nsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hadh28nsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:people-carry-solid" {...props}></Icon>
