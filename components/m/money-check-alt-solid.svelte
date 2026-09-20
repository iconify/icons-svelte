<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8wyo1b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w8wyo1b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:money-check-alt-solid" {...props}></Icon>
