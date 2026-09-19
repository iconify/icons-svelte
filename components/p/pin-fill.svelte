<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lelvr5blt.css';
import '../../css/t/troxz-_lw.css';
import '../../css/p/pu0y4pgpa.css';
import '../../css/p/p48ewxbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="lelvr5blt"/><path class="troxz-_lw"/><path class="pu0y4pgpa"/><path class="p48ewxbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:pin-fill" {...props}></Icon>
