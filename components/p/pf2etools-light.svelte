<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-5qssb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k-5qssb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pf2etools-light" {...props}></Icon>
