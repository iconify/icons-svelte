<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut23oebnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ut23oebnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-erpnext-dark" {...props}></Icon>
