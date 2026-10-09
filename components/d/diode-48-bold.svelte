<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht2v78f-m.css';
import '../../css/u/u431zobpm.css';
import '../../css/c/cbzm5ebwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ht2v78f-m"/><path class="u431zobpm"/><path class="cbzm5ebwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:diode-48-bold" {...props}></Icon>
