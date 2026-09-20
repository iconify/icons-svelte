<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-bnru2rv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g-bnru2rv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:border-none-solid" {...props}></Icon>
