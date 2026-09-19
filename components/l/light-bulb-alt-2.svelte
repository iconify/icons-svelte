<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of4_u7bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b of4_u7bux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:light-bulb-alt-2" {...props}></Icon>
