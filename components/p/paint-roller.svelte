<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzl-74xew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzl-74xew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:paint-roller" {...props}></Icon>
