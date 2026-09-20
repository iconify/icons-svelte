<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mibv8f8tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mibv8f8tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:crosswalk-markings-ladder" {...props}></Icon>
