<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nua10xqcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nua10xqcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:merge-node" {...props}></Icon>
