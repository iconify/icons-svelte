<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnu9x_btz.css';
import '../../css/s/sbulpizdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qnu9x_btz"/><path clip-rule="evenodd" class="sbulpizdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:integration-security" {...props}></Icon>
