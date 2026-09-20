<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcc5x3bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcc5x3bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:line-arrow-transfer-horizontal-1-remix" {...props}></Icon>
