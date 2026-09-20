<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsic9tbse.css';
import '../../css/f/fr9wnwjpk.css';
import '../../css/c/c6vuqnbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lsic9tbse"/><path class="fr9wnwjpk"/><path class="c6vuqnbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:re-director" {...props}></Icon>
