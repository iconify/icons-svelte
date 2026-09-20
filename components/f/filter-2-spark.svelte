<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_momnr0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_momnr0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-2-spark" {...props}></Icon>
