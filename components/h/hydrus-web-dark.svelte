<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqd6bpb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qqd6bpb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hydrus-web-dark" {...props}></Icon>
