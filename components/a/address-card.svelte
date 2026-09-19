<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_klh3bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="q_klh3bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:address-card" {...props}></Icon>
