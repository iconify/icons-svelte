<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byuv76u1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="byuv76u1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:building-office-2-20-solid" {...props}></Icon>
