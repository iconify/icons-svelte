<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l9di_s0jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="l9di_s0jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:kotlin" {...props}></Icon>
