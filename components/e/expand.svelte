<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2wzqxngm.css';
import '../../css/b/bb_4oobxv.css';
import '../../css/e/ej16q4bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d2wzqxngm"/><path class="bb_4oobxv"/><path class="ej16q4bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:expand" {...props}></Icon>
