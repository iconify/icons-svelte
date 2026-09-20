<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wecphb13q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wecphb13q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:old-navy-dark" {...props}></Icon>
