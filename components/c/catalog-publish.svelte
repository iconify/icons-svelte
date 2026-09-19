<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs0839n8x.css';
import '../../css/t/ta7x8sbgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cs0839n8x"/><path class="ta7x8sbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:catalog-publish" {...props}></Icon>
