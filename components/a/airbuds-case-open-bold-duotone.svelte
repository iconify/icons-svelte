<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r__f3wn0s.css';
import '../../css/t/tpa5nbb8v.css';
import '../../css/l/lcnzvy4sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r__f3wn0s"/><path class="tpa5nbb8v"/><path class="lcnzvy4sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-case-open-bold-duotone" {...props}></Icon>
