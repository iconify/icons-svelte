<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivoyk3bek.css';
import '../../css/f/fmgf82-9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ivoyk3bek"/><path class="fmgf82-9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:compass-rose-n" {...props}></Icon>
