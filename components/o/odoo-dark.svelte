<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q03bp-btw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q03bp-btw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:odoo-dark" {...props}></Icon>
