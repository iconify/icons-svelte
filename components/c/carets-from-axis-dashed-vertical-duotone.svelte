<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/osq_iiixh.css';
import '../../css/m/mibkzifbb.css';
import '../../css/b/b7bwx7byr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="osq_iiixh"/><path class="mibkzifbb"/><path class="b7bwx7byr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:carets-from-axis-dashed-vertical-duotone" {...props}></Icon>
