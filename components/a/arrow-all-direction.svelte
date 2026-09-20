<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgdm3ebfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="xgdm3ebfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:arrow-all-direction" {...props}></Icon>
