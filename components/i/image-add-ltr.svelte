<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrm89iuuq.css';
import '../../css/y/y0bmns4xv.css';
import '../../css/k/k79q3xboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hrm89iuuq"/><path class="y0bmns4xv"/><circle class="k79q3xboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-add-ltr" {...props}></Icon>
