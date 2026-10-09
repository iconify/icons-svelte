<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyts_6b4x.css';
import '../../css/f/fu4k6tlst.css';
import '../../css/x/xpbh4hvld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kyts_6b4x"/><path class="fu4k6tlst"/><path class="xpbh4hvld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blueprint-48-bold" {...props}></Icon>
