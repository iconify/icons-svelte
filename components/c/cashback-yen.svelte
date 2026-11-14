<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px8f0sm6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px8f0sm6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cashback-yen" {...props}></Icon>
