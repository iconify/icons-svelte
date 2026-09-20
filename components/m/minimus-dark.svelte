<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwad_gb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwad_gb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:minimus-dark" {...props}></Icon>
