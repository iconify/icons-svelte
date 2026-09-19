<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_js4bbia.css';
import '../../css/d/d47xi2b9o.css';
import '../../css/b/be97_nbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j_js4bbia"/><path class="d47xi2b9o"/><path class="be97_nbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:peso" {...props}></Icon>
