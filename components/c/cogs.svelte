<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/meiu8obml.css';
import '../../css/g/gvguocbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="meiu8obml"/><path class="gvguocbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:cogs" {...props}></Icon>
