<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc5gbb7ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mc5gbb7ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:fill-drip" {...props}></Icon>
