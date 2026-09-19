<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw2n_kb8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aw2n_kb8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-set" {...props}></Icon>
