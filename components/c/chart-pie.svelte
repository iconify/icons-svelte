<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pffhewbcz.css';
import '../../css/b/bcag0_byz.css';
import '../../css/m/m3mc73wcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pffhewbcz"/><path class="bcag0_byz"/><path class="m3mc73wcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:chart-pie" {...props}></Icon>
