<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpxqa_bcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bpxqa_bcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:gamepad-20-solid" {...props}></Icon>
