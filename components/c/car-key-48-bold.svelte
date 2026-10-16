<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3mfcsb3n.css';
import '../../css/s/snd_4ib6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z3mfcsb3n"/><path class="snd_4ib6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-key-48-bold" {...props}></Icon>
