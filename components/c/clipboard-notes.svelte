<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlgp2b63v.css';
import '../../css/x/x5yrrkbss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="mlgp2b63v"/><path class="x5yrrkbss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:clipboard-notes" {...props}></Icon>
