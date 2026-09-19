<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvzym5b5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="nvzym5b5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:cc-apple-pay" {...props}></Icon>
