<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtus33btr.css';
import '../../css/z/zeit0ibdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="qtus33btr"/><path class="zeit0ibdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinepods" {...props}></Icon>
