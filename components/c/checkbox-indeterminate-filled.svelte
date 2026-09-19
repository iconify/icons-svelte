<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw0jjfbol.css';
import '../../css/a/a-uf0ibir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dw0jjfbol"/><path class="a-uf0ibir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:checkbox-indeterminate-filled" {...props}></Icon>
