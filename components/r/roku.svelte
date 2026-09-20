<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mep9_ebte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mep9_ebte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:roku" {...props}></Icon>
