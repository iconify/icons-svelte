<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdounc8nc.css';
import '../../css/i/il9s_hbni.css';
import '../../css/p/p5uqo6r1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mdounc8nc"/><path class="il9s_hbni"/><path class="p5uqo6r1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:imbalance-20-bold" {...props}></Icon>
