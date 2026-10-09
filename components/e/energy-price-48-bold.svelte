<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opn24tbwg.css';
import '../../css/o/ov--w3k6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="opn24tbwg"/><path class="ov--w3k6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-price-48-bold" {...props}></Icon>
