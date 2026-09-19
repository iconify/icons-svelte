<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emfgklaqt.css';
import '../../css/c/cvwa4ha8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="emfgklaqt"/><path class="cvwa4ha8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direction-fork-filled" {...props}></Icon>
