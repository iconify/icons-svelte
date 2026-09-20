<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0_5tr2wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="b0_5tr2wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:cloud-solid" {...props}></Icon>
