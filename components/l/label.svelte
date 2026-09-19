<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_2-9c3fr.css';
import '../../css/z/zq-0s9biw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s_2-9c3fr"/><path class="zq-0s9biw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:label" {...props}></Icon>
