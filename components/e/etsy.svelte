<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa4o83b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qa4o83b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:etsy" {...props}></Icon>
