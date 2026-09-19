<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/phqj96tym.css';
import '../../css/j/ji09qr2cx.css';
import '../../css/w/wv7su1lfa.css';
import '../../css/q/qtqbarb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="phqj96tym"/><path class="ji09qr2cx"/><circle class="wv7su1lfa"/><circle class="qtqbarb1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:remote-control-one" {...props}></Icon>
