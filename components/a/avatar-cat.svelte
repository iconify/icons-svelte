<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/v/vdyk84bdd.css';
import '../../css/q/qbmxxsbra.css';
import '../../css/r/ryjqceb3q.css';
import '../../css/q/qbzlvdb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="vdyk84bdd wm-shadow"/><path class="qbmxxsbra wm-shadow"/><path class="ryjqceb3q"/><path class="qbzlvdb3n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:avatar-cat" {...props}></Icon>
