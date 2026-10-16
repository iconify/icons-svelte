<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u95e4sw8e.css';
import '../../css/l/la89sqemp.css';
import '../../css/d/d1s4subwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u95e4sw8e"/><path class="la89sqemp"/><path class="d1s4subwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clipboard-copy-48-bold" {...props}></Icon>
