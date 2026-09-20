<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyye1n_ow.css';
import '../../css/m/mkgj1odis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyye1n_ow"/><path class="mkgj1odis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:reclaimerr-dark" {...props}></Icon>
