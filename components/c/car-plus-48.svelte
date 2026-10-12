<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfdfq4bue.css';
import '../../css/f/ftsh3hbxo.css';
import '../../css/b/bbxn-dufo.css';
import '../../css/k/kem81wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cfdfq4bue"/><path class="ftsh3hbxo"/><path class="bbxn-dufo"/><path class="kem81wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:car-plus-48" {...props}></Icon>
