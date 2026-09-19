<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl4cs1byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fl4cs1byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-minus-20-solid" {...props}></Icon>
