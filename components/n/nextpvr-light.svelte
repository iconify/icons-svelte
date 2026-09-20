<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqc2gxb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cqc2gxb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextpvr-light" {...props}></Icon>
