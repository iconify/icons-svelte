<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2auhh-bp.css';
import '../../css/v/vwi05mrad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="a2auhh-bp"/><path class="vwi05mrad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:clipboard-pencil" {...props}></Icon>
