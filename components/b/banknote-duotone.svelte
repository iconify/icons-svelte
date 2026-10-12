<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aq8lyzp4d.css';
import '../../css/c/cj2g5-b5u.css';
import '../../css/h/hmmcrtbfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="aq8lyzp4d"/><path class="cj2g5-b5u"/><path class="hmmcrtbfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banknote-duotone" {...props}></Icon>
