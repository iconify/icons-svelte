<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke_77zjpb.css';
import '../../css/b/bblukg9bh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ke_77zjpb"/><path class="bblukg9bh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-off-20-bold" {...props}></Icon>
