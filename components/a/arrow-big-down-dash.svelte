<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7_zzgbxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7_zzgbxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-big-down-dash" {...props}></Icon>
