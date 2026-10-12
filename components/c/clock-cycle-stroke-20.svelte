<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygkahxbsa.css';
import '../../css/e/e_i9g7bpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ygkahxbsa"/><path class="e_i9g7bpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-cycle-stroke-20" {...props}></Icon>
