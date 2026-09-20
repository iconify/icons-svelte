<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr5y6mbwg.css';
import '../../css/x/x6bcvoimv.css';
import '../../css/a/a49kqqbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pr5y6mbwg"/><path class="x6bcvoimv"/><path class="a49kqqbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:design-tool-fibonacci-bold" {...props}></Icon>
