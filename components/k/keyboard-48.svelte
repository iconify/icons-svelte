<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7olx61gw.css';
import '../../css/p/pru8skb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r7olx61gw"/><path class="pru8skb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:keyboard-48" {...props}></Icon>
