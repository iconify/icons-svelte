<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsqzmj9ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsqzmj9ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:alert-triangle" {...props}></Icon>
