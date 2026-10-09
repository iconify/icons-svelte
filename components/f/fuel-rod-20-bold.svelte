<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p169fcb-f.css';
import '../../css/z/z26u7ebdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p169fcb-f"/><path class="z26u7ebdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-rod-20-bold" {...props}></Icon>
