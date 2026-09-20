<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ket-5fbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ket-5fbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filerun-dark" {...props}></Icon>
