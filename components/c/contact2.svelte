<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/som5wvb2y.css';
import '../../css/q/qj2dxhekm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="som5wvb2y"/><path class="qj2dxhekm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:contact2" {...props}></Icon>
