<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph9p3hbni.css';
import '../../css/m/mzc4obb9m.css';
import '../../css/o/obwihtkas.css';
import '../../css/p/p-yajvbte.css';
import '../../css/y/ycnp-c5_c.css';
import '../../css/m/mo44l72mq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ph9p3hbni"/><path class="mzc4obb9m"/><path class="obwihtkas"/><path class="p-yajvbte"/><path class="ycnp-c5_c"/><path class="mo44l72mq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:monkeysee" {...props}></Icon>
