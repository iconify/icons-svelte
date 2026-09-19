<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6w7p4bnr.css';
import '../../css/a/aw9rmcz9o.css';
import '../../css/g/g8mz2db_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u6w7p4bnr"/><path class="aw9rmcz9o"/><path class="g8mz2db_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:lu-1x1" {...props}></Icon>
