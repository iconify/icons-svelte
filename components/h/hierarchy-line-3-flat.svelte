<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv0qhybxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bv0qhybxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:hierarchy-line-3-flat" {...props}></Icon>
