<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmultrkok.css';
import '../../css/r/rvr6ihv2q.css';
import '../../css/g/gu9qoyb5a.css';
import '../../css/z/z5qwait0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mmultrkok"/><path class="rvr6ihv2q"/><path class="gu9qoyb5a"/><path class="z5qwait0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-candlestick-48-bold" {...props}></Icon>
