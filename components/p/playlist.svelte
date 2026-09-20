<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8n5xcpzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o8n5xcpzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:playlist" {...props}></Icon>
