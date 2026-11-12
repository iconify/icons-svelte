<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfl_6ccyr.css';
import '../../css/e/epc2a1c0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lfl_6ccyr"/><path class="epc2a1c0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-sharepoint-2013" {...props}></Icon>
