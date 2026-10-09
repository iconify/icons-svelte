<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxgyedcli.css';
import '../../css/v/vr6bwvoqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zxgyedcli"/><path class="vr6bwvoqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:offshore-substation-20-bold" {...props}></Icon>
