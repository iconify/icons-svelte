<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqpt0ub4e.css';
import '../../css/h/hpyrhjbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqpt0ub4e"/><path class="hpyrhjbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layer-arrow-down-filled" {...props}></Icon>
