<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8xwu9g6i.css';
import '../../css/g/gxciwdbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="s8xwu9g6i"/><path class="gxciwdbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:phone-portrait-outline" {...props}></Icon>
