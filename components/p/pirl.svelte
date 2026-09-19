<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ifmzx9bik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ifmzx9bik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:pirl" {...props}></Icon>
