<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_554nb3a.css';
import '../../css/c/cxh3ar5_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":9,"height":16};
const content = `<path class="f_554nb3a"/><path class="cxh3ar5_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:arrowup" {...props}></Icon>
