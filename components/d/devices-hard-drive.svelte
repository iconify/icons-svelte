<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oniaw-bgi.css';
import '../../css/p/pva-szciw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oniaw-bgi"/><path clip-rule="evenodd" class="pva-szciw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-hard-drive" {...props}></Icon>
