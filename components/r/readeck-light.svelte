<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qobvp-qlo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qobvp-qlo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readeck-light" {...props}></Icon>
