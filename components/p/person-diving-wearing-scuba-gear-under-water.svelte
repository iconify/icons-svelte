<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfe-pzb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zfe-pzb2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-diving-wearing-scuba-gear-under-water" {...props}></Icon>
