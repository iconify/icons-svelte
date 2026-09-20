<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akmt2_8eg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="akmt2_8eg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:badge-20-solid" {...props}></Icon>
