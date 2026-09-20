<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1_dfrd-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b1_dfrd-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:package-dimension-solid" {...props}></Icon>
