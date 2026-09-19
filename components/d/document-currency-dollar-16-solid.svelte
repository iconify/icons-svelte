<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7_-kbcvl.css';
import '../../css/d/dqlj_tyvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h7_-kbcvl"/><path clip-rule="evenodd" class="dqlj_tyvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-dollar-16-solid" {...props}></Icon>
