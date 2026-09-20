<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdduppbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bdduppbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linkace-dark" {...props}></Icon>
