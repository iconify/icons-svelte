<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo_ch73fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qo_ch73fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:lowrise-apartment-building" {...props}></Icon>
