<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r9tcbvs3n.css';
import '../../css/f/fn9on300s.css';
import '../../css/h/hdqah4lam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r9tcbvs3n"/><path class="fn9on300s"/><path class="hdqah4lam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:palette-duotone" {...props}></Icon>
