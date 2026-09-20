<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pme45vd5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pme45vd5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netvisor-dark" {...props}></Icon>
