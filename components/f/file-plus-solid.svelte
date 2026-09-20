<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6h1arbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="t6h1arbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-plus-solid" {...props}></Icon>
