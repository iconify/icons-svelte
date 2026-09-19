<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc_uhhbsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="pc_uhhbsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:ban" {...props}></Icon>
