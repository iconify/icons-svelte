<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqee7sb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tqee7sb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-transfer-horizontal-large-1-solid" {...props}></Icon>
