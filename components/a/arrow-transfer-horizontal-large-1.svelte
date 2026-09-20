<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5hd9r9ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5hd9r9ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:arrow-transfer-horizontal-large-1" {...props}></Icon>
