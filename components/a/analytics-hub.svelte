<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnn_acbmc.css';
import '../../css/l/lrp6bibkl.css';
import '../../css/c/c-9udcc7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnn_acbmc"/><path class="lrp6bibkl"/><path class="c-9udcc7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:analytics-hub" {...props}></Icon>
