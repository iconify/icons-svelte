<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgk1dmbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgk1dmbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:christmas-tree" {...props}></Icon>
