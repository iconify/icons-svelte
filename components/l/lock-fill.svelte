<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djo_9gben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djo_9gben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:lock-fill" {...props}></Icon>
