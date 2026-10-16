<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gerffvb_e.css';
import '../../css/v/v5ofbw7zr.css';
import '../../css/m/m91h_kbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gerffvb_e"/><path class="v5ofbw7zr"/><path class="m91h_kbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-9v-48" {...props}></Icon>
