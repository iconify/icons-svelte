<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-bjy1bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k-bjy1bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flower-alt-solid" {...props}></Icon>
