<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldjgpjbom.css';
import '../../css/c/chq_v_ohg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ldjgpjbom"/><path class="chq_v_ohg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-merge-filled" {...props}></Icon>
