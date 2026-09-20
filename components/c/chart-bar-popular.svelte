<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t00icf71t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t00icf71t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chart-bar-popular" {...props}></Icon>
