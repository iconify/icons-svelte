<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnu9x_btz.css';
import '../../css/u/uf4j-xoii.css';
import '../../css/k/kk9m20bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qnu9x_btz"/><path clip-rule="evenodd" class="uf4j-xoii"/><path clip-rule="evenodd" class="kk9m20bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:integration-observability" {...props}></Icon>
