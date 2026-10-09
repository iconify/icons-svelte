<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffy_fhb2a.css';
import '../../css/n/n8n104bks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ffy_fhb2a"/><path class="n8n104bks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-efficiency-48-bold" {...props}></Icon>
