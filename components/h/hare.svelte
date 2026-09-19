<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krn-s63up.css';
import '../../css/s/smbx2_k0z.css';
import '../../css/v/vto-p9r5y.css';
import '../../css/b/be-8-kdwh.css';
import '../../css/z/zs83a7b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="krn-s63up"/><path class="smbx2_k0z"/><circle class="vto-p9r5y"/><circle class="be-8-kdwh"/><path class="zs83a7b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:hare" {...props}></Icon>
