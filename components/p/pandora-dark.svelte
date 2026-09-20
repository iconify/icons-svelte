<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngnqm6b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ngnqm6b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pandora-dark" {...props}></Icon>
