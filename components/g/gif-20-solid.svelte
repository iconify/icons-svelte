<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arcph36co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="arcph36co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gif-20-solid" {...props}></Icon>
