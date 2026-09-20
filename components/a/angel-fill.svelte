<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j65g2nbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j65g2nbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:angel-fill" {...props}></Icon>
