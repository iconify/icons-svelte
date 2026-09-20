<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf81h_pns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="wf81h_pns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:matrix-dark" {...props}></Icon>
