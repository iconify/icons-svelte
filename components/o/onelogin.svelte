<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8xu4hqsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":142.8,"height":35.2};
const content = `<path class="r8xu4hqsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onelogin" {...props}></Icon>
