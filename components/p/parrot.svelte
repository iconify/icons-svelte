<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc_qceb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lc_qceb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:parrot" {...props}></Icon>
