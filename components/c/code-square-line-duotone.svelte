<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b_mqzbbbw.css';
import '../../css/r/r6t4zeiqh.css';
import '../../css/l/lr4e9yb5j.css';
import '../../css/l/lxnzn9nmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b_mqzbbbw"/><path class="r6t4zeiqh"/><path class="lr4e9yb5j"/><path class="lxnzn9nmw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-square-line-duotone" {...props}></Icon>
