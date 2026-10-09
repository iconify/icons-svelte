<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbmfgacnw.css';
import '../../css/d/d90ivtb7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wbmfgacnw"/><path class="d90ivtb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:prism-20-bold" {...props}></Icon>
