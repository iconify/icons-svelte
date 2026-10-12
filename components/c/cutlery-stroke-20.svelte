<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0cnxybhb.css';
import '../../css/q/qeky-4bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k0cnxybhb"/><path class="qeky-4bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cutlery-stroke-20" {...props}></Icon>
