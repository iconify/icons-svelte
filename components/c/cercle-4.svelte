<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_h9vnu3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n_h9vnu3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:cercle-4" {...props}></Icon>
