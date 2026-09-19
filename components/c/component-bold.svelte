<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fski4lbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fski4lbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:component-bold" {...props}></Icon>
