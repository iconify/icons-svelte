<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxrdkngpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oxrdkngpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-start-fill" {...props}></Icon>
