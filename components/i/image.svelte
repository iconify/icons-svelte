<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8qmtb0vg.css';
import '../../css/w/wvqn8smga.css';
import '../../css/l/l85zn4b0m.css';
import '../../css/t/tqx96999q.css';
import '../../css/o/otjwedhbq.css';
import '../../css/n/n-inml2tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g transform="scale(3.77953)" class="i8qmtb0vg"><rect class="wvqn8smga"/><path class="l85zn4b0m"/><path class="tqx96999q"/><path class="otjwedhbq"/><circle class="n-inml2tz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gala:image" {...props}></Icon>
