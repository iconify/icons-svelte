<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip4n_nb-a.css';
import '../../css/n/nwb7bcc2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ip4n_nb-a"/><path class="nwb7bcc2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-label-48" {...props}></Icon>
