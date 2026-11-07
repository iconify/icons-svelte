<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kubz8lo_c.css';
import '../../css/e/elic3l99c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kubz8lo_c"/><path class="elic3l99c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-bold-duotone" {...props}></Icon>
