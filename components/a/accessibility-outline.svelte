<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsf0-2bjx.css';
import '../../css/b/bouxdeh8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="xsf0-2bjx"/><path class="bouxdeh8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:accessibility-outline" {...props}></Icon>
