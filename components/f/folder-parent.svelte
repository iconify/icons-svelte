<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt4rfofpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bt4rfofpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-parent" {...props}></Icon>
