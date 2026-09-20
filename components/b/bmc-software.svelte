<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukhx47_lj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukhx47_lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:bmc-software" {...props}></Icon>
