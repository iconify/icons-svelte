<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef0-97kcs.css';
import '../../css/p/plk_--7pi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ef0-97kcs"/><path class="plk_--7pi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plug-uk-48-bold" {...props}></Icon>
