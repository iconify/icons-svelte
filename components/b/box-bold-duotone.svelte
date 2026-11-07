<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kngzmjb8s.css';
import '../../css/g/g0-11mmdk.css';
import '../../css/g/g23e_tb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kngzmjb8s"/><path class="g0-11mmdk"/><path class="g23e_tb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:box-bold-duotone" {...props}></Icon>
