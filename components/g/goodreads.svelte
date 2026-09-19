<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1s6nvbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v1s6nvbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:goodreads" {...props}></Icon>
