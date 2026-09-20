<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfv3j0v9a.css';
import '../../css/h/hbhflsb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="qfv3j0v9a"/><path class="hbhflsb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:cog" {...props}></Icon>
