<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nekm4w3ue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nekm4w3ue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-cloud-dark" {...props}></Icon>
