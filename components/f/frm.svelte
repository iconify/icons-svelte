<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgxln0b_c.css';
import '../../css/h/hlm14cb_n.css';
import '../../css/h/h-clu1byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgxln0b_c"/><path class="hlm14cb_n"/><path class="h-clu1byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:frm" {...props}></Icon>
