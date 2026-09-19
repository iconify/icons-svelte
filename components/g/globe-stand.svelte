<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-ltem8ez.css';
import '../../css/p/p-0vs8b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-ltem8ez"/><path class="p-0vs8b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-stand" {...props}></Icon>
