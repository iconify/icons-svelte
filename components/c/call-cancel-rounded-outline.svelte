<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi6_f9yez.css';
import '../../css/o/o4sar_bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xi6_f9yez"/><path clip-rule="evenodd" class="o4sar_bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-cancel-rounded-outline" {...props}></Icon>
