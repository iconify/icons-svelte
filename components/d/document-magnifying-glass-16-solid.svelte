<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu5lx12xc.css';
import '../../css/z/zla48o_aw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gu5lx12xc"/><path clip-rule="evenodd" class="zla48o_aw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-magnifying-glass-16-solid" {...props}></Icon>
