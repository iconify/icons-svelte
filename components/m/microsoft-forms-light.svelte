<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-au2bijw.css';
import '../../css/j/jv20dbsyk.css';
import '../../css/i/ijutckbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q-au2bijw"/><path class="jv20dbsyk"/><path class="ijutckbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-forms-light" {...props}></Icon>
