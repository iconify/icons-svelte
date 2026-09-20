<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2lokmb9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2lokmb9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:goodreads" {...props}></Icon>
