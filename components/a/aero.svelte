<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hefuzsyto.css';
import '../../css/h/hy2durjjx.css';
import '../../css/y/y3v2sl6-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":51.74,"height":70};
const content = `<path class="hefuzsyto"/><path class="hy2durjjx"/><path class="y3v2sl6-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:aero" {...props}></Icon>
