<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpn68nbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qpn68nbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:animal-tick-outline" {...props}></Icon>
