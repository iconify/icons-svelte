<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvgnqf_wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bvgnqf_wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:exit" {...props}></Icon>
