<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eggr4hkfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eggr4hkfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:budgetbee-light" {...props}></Icon>
