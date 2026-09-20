<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xke0zjbte.css';
import '../../css/i/itxo1tb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xke0zjbte"/><path class="itxo1tb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pillar" {...props}></Icon>
