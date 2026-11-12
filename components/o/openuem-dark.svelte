<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggvn7iwto.css';
import '../../css/x/x5x2_1b7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ggvn7iwto"/><path class="x5x2_1b7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openuem-dark" {...props}></Icon>
