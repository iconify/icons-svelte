<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfzk-m7le.css';
import '../../css/s/s4tacdvsa.css';
import '../../css/w/wabb2o_wh.css';
import '../../css/g/gsl21kb0m.css';
import '../../css/c/cijt8bpva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nfzk-m7le"/><path class="s4tacdvsa"/><path class="wabb2o_wh"/><path class="gsl21kb0m"/><path class="cijt8bpva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:island-20-bold" {...props}></Icon>
