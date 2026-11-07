<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctk3lmxrt.css';
import '../../css/i/ihwrm7b8t.css';
import '../../css/m/mlbyvsbes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctk3lmxrt"/><path class="ihwrm7b8t"/><path class="mlbyvsbes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lightbulb-bolt-bold-duotone" {...props}></Icon>
