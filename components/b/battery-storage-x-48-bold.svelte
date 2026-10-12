<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih35z4x5n.css';
import '../../css/l/l7s7xcc2s.css';
import '../../css/c/ckludqbvv.css';
import '../../css/e/e3y16ob3v.css';
import '../../css/s/sfb8rqn9v.css';
import '../../css/k/ksydp3lsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ih35z4x5n"/><path class="l7s7xcc2s"/><path class="ckludqbvv"/><path class="e3y16ob3v"/><path class="sfb8rqn9v"/><path class="ksydp3lsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-storage-x-48-bold" {...props}></Icon>
