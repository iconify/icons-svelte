<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp8f-vbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zp8f-vbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-merge" {...props}></Icon>
