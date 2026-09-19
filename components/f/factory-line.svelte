<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdsarc1ua.css';
import '../../css/g/gphd1nbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="zdsarc1ua"/><path class="gphd1nbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:factory-line" {...props}></Icon>
