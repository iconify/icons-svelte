<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjv4dy7qr.css';
import '../../css/a/adqsiqg3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tjv4dy7qr"/><path class="adqsiqg3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:caliper-20-bold" {...props}></Icon>
