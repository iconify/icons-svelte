<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk9ky-bpe.css';
import '../../css/q/qnu9x_btz.css';
import '../../css/q/qgw5s4bhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="mk9ky-bpe"/><path class="qnu9x_btz"/><path clip-rule="evenodd" class="qgw5s4bhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:integration-general" {...props}></Icon>
