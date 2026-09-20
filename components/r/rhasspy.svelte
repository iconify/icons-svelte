<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iv4lvww3m.css';
import '../../css/p/pug9g9bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<ellipse class="iv4lvww3m"/><path class="pug9g9bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rhasspy" {...props}></Icon>
