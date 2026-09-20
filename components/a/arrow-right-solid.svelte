<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7as0ab6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e7as0ab6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-right-solid" {...props}></Icon>
