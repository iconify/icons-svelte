<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlosulb6e.css';
import '../../css/b/b9isaca6x.css';
import '../../css/b/bfo_vpyhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wlosulb6e"/><path class="b9isaca6x"/><path class="bfo_vpyhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-dropper-48-bold" {...props}></Icon>
