<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/neuquygwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1408};
const content = `<path class="neuquygwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cart-plus" {...props}></Icon>
