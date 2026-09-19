<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzb2efb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="tzb2efb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:funnel-20-solid" {...props}></Icon>
