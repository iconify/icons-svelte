<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bixh1wb9y.css';
import '../../css/h/hzjf5hkxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bixh1wb9y"/><path class="hzjf5hkxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:draught-proofing-20-bold" {...props}></Icon>
