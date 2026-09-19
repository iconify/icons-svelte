<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-i5jcr0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l-i5jcr0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:privacy" {...props}></Icon>
