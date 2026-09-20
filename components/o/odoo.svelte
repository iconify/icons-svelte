<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb9c2sbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rb9c2sbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:odoo" {...props}></Icon>
