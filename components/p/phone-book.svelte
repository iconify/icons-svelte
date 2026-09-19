<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv8augtve.css';
import '../../css/z/z1i2occ_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv8augtve"/><path class="z1i2occ_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:phone-book" {...props}></Icon>
