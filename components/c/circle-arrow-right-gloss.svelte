<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjefz4hqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjefz4hqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-arrow-right-gloss" {...props}></Icon>
