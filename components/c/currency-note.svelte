<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_80cab1p.css';
import '../../css/g/gt9eulz_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s_80cab1p"/><path class="gt9eulz_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:currency-note" {...props}></Icon>
