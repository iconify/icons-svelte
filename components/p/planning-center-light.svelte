<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcy09obnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pcy09obnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planning-center-light" {...props}></Icon>
