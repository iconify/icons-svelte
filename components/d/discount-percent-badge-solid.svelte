<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbp56ycrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="cbp56ycrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:discount-percent-badge-solid" {...props}></Icon>
