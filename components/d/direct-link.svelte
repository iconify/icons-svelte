<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxv_pcivz.css';
import '../../css/c/clqjdubcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qxv_pcivz"/><path class="clqjdubcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:direct-link" {...props}></Icon>
