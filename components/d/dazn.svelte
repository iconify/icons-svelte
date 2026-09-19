<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnc2a2bwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bnc2a2bwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:dazn" {...props}></Icon>
