<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc1n2ug0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nc1n2ug0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maybe-dark" {...props}></Icon>
