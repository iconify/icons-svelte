<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew9mh_xxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew9mh_xxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:jackhammer" {...props}></Icon>
