<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuxpu25hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uuxpu25hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:apple" {...props}></Icon>
