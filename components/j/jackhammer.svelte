<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p643z7b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="p643z7b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:jackhammer" {...props}></Icon>
