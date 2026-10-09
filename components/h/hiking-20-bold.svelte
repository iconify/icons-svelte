<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9jgtejbn.css';
import '../../css/e/ekd7jsf_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r9jgtejbn"/><path class="ekd7jsf_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hiking-20-bold" {...props}></Icon>
