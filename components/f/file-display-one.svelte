<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pu4i87gug.css';
import '../../css/w/wdnwhgycf.css';
import '../../css/l/lysehlayp.css';
import '../../css/p/p5fvr-byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="pu4i87gug"/><path class="wdnwhgycf"/><path class="lysehlayp"/><path class="p5fvr-byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:file-display-one" {...props}></Icon>
