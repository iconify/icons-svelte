<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1sv60b0b.css';
import '../../css/j/jls6yjbxr.css';
import '../../css/j/j_dws6b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f1sv60b0b"/><path class="jls6yjbxr"/><path class="j_dws6b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:angle-grinder-48-bold" {...props}></Icon>
