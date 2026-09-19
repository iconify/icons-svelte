<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0m40jtsp.css';
import '../../css/t/tjes3mbwb.css';
import '../../css/p/pae_c0_fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g0m40jtsp"/><path class="tjes3mbwb"/><path class="pae_c0_fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bus" {...props}></Icon>
