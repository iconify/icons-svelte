<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp255lbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pp255lbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:currency-euro" {...props}></Icon>
