<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcp2pkb_d.css';
import '../../css/a/acu1a62dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gcp2pkb_d"/><path class="acu1a62dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pallet-48" {...props}></Icon>
