<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tdiwa3b_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tdiwa3b_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:battery-empty-2-remix" {...props}></Icon>
