<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs413g27j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zs413g27j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cut-solid" {...props}></Icon>
