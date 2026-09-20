<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr9277r9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vr9277r9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:marpui" {...props}></Icon>
