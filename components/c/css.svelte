<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t78rjtomt.css';
import '../../css/h/hn34necwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t78rjtomt"/><path class="hn34necwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:css" {...props}></Icon>
