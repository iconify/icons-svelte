<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjmcju-mi.css';
import '../../css/p/pvhv_7sne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjmcju-mi"/><path class="pvhv_7sne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:power-bold-duotone" {...props}></Icon>
