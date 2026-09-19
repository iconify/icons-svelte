<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-m54achm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i-m54achm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-20-solid" {...props}></Icon>
