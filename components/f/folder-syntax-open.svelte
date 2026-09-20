<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixetddbeg.css';
import '../../css/z/z4tn2nb1x.css';
import '../../css/r/rysw60b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixetddbeg"/><path class="z4tn2nb1x"/><path class="rysw60b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-syntax-open" {...props}></Icon>
