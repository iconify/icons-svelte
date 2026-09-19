<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tti2g3bpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tti2g3bpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:minus-small-20-solid" {...props}></Icon>
