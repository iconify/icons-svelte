<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twga4rbxo.css';
import '../../css/l/ltcgo_b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="twga4rbxo"/><path class="ltcgo_b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:brine-pond-48" {...props}></Icon>
