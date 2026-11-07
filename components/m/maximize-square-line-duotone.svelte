<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hb6t3lb4p.css';
import '../../css/a/ajyuzgzsc.css';
import '../../css/l/lxnzn9nmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hb6t3lb4p"/><path class="ajyuzgzsc"/><path class="lxnzn9nmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:maximize-square-line-duotone" {...props}></Icon>
