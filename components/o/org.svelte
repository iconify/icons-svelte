<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkfottbas.css';
import '../../css/c/c3z6yg-qu.css';
import '../../css/w/w2k4c4jrl.css';
import '../../css/j/j40lfpbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kkfottbas"/><path class="c3z6yg-qu"/><path class="w2k4c4jrl"/><path class="j40lfpbca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:org" {...props}></Icon>
