<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7o_6ab8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7o_6ab8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-crm-dark" {...props}></Icon>
