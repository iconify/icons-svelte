<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hine55bkd.css';
import '../../css/e/e00g5nbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hine55bkd"/><path class="e00g5nbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-sentiment" {...props}></Icon>
