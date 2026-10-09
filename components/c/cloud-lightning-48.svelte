<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlah_2byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nlah_2byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-lightning-48" {...props}></Icon>
