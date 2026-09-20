<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po1nrc4wh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="po1nrc4wh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-pinterest" {...props}></Icon>
