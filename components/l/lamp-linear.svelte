<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ick8o1b-y.css';
import '../../css/a/a-4dztb1w.css';
import '../../css/q/q54d_4iej.css';
import '../../css/v/vnmkxmasi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ick8o1b-y"/><path class="a-4dztb1w"/><path class="q54d_4iej"/><path class="vnmkxmasi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lamp-linear" {...props}></Icon>
