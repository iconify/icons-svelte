<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t84lhjjrc.css';
import '../../css/d/dqytc7seb.css';
import '../../css/v/v2crmy61y.css';
import '../../css/g/g2bf17kpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="t84lhjjrc"/><path clip-rule="evenodd" class="dqytc7seb"/><path class="v2crmy61y"/><path clip-rule="evenodd" class="g2bf17kpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plane-departure-outline" {...props}></Icon>
