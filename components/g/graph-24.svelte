<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhr---bpz.css';
import '../../css/h/h_4f1111a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhr---bpz"/><path class="h_4f1111a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-24" {...props}></Icon>
