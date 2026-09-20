<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dy9a1bbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dy9a1bbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atomic-crm" {...props}></Icon>
