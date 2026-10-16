<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vo53krbdf.css';
import '../../css/v/vf-n7zb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vo53krbdf"/><path class="vf-n7zb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ev-parking-20" {...props}></Icon>
