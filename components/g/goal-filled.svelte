<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx50cdblo.css';
import '../../css/s/skotkdb7i.css';
import '../../css/k/keplz_bav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx50cdblo"/><path class="skotkdb7i"/><path class="keplz_bav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:goal-filled" {...props}></Icon>
