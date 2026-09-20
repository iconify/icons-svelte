<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx0rambyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mx0rambyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maxun" {...props}></Icon>
