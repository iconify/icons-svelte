<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov8y93bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ov8y93bhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:aerospike" {...props}></Icon>
