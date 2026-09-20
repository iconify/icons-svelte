<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmejzn51m.css';
import '../../css/x/xc7m02d-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fmejzn51m"/><path class="ouiIcon__fillSecondary xc7m02d-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:ml-classification-job" {...props}></Icon>
