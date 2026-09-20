<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqu2_e4mu.css';
import '../../css/i/i-02_nl2g.css';
import '../../css/e/eyc-0ib3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="pqu2_e4mu"/><path class="i-02_nl2g"/><path class="eyc-0ib3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:redlib" {...props}></Icon>
