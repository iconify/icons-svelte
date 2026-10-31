<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nehmr7u7k.css';
import '../../css/d/d1xosacnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="nehmr7u7k"/><path class="d1xosacnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:maltese-cross" {...props}></Icon>
