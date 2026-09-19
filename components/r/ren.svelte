<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi3sprbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vi3sprbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:ren" {...props}></Icon>
