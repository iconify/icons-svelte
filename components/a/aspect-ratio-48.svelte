<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsmhpgwcs.css';
import '../../css/f/fc_5vwb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tsmhpgwcs"/><path class="fc_5vwb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:aspect-ratio-48" {...props}></Icon>
