<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn-tllbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dn-tllbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:admin-site-alt" {...props}></Icon>
