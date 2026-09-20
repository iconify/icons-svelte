<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0gdhngja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0gdhngja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:arrmatey-dark" {...props}></Icon>
