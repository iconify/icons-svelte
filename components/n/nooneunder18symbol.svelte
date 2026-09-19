<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot8rfwb8w.css';
import '../../css/a/a23i8nphm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ot8rfwb8w"/><path class="a23i8nphm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:nooneunder18symbol" {...props}></Icon>
