<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5xx1xbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t5xx1xbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:add-pdf-solid" {...props}></Icon>
