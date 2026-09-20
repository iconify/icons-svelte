<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kci_ppyst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kci_ppyst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:medical-instrument-scalpel-bold" {...props}></Icon>
