<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpa070kua.css';
import '../../css/r/rsxgxvbwd.css';
import '../../css/z/z_ydjmbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zpa070kua"/><path class="rsxgxvbwd"/><path class="z_ydjmbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:printer-2-bold" {...props}></Icon>
