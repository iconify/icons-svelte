<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep7_n76dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ep7_n76dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-curve-up-right-20-solid" {...props}></Icon>
