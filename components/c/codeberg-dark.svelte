<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnqpocbhp.css';
import '../../css/m/m36y1-ioy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rnqpocbhp"/><path class="m36y1-ioy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:codeberg-dark" {...props}></Icon>
