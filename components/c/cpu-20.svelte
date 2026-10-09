<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af6ze-elo.css';
import '../../css/v/vgqa32bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="af6ze-elo"/><path class="vgqa32bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cpu-20" {...props}></Icon>
