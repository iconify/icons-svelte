<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iemmtbc_j.css';
import '../../css/j/jr2o5bbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":346,"height":434};
const content = `<path class="iemmtbc_j"/><path class="cls-1 jr2o5bbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:heimdall" {...props}></Icon>
