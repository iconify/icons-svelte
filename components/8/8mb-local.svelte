<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci6-fubhr.css';
import '../../css/v/vqmzdlotb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ci6-fubhr"/><path class="vqmzdlotb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:8mb-local" {...props}></Icon>
