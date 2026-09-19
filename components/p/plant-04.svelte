<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irnkvnbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="irnkvnbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:plant-04" {...props}></Icon>
