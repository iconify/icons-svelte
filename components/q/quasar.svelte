<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doy7itbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50.843,"height":50.843};
const content = `<path class="doy7itbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:quasar" {...props}></Icon>
