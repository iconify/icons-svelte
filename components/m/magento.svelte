<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar2gpjbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ar2gpjbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:magento" {...props}></Icon>
