<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mz09tfcia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mz09tfcia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-rainy" {...props}></Icon>
