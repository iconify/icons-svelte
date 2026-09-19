<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwx7_1bes.css';
import '../../css/h/ha1q3jlnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hwx7_1bes"/><path class="ha1q3jlnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:layer-alt-add-o" {...props}></Icon>
