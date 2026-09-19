<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9uro8i1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9uro8i1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cashback-yen" {...props}></Icon>
