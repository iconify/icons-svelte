<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oat_n_6bp.css';
import '../../css/q/qbbwyjbnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oat_n_6bp"/><path class="qbbwyjbnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hand-truck-filled" {...props}></Icon>
