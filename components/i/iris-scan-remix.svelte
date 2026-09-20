<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5knuwi0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5knuwi0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:iris-scan-remix" {...props}></Icon>
