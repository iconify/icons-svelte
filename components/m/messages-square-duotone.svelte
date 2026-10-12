<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pr317i25u.css';
import '../../css/l/lazq1ab7l.css';
import '../../css/e/em-eh2bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pr317i25u"/><path class="lazq1ab7l"/><path class="em-eh2bsd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:messages-square-duotone" {...props}></Icon>
