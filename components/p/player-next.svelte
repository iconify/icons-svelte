<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dytf-3bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dytf-3bsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-next" {...props}></Icon>
