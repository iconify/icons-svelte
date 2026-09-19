<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lilc0nbbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lilc0nbbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-box-middle-right" {...props}></Icon>
