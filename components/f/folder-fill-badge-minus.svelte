<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afe3ybcfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="afe3ybcfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:folder-fill-badge-minus" {...props}></Icon>
