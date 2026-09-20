<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq9b7uf9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tq9b7uf9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:anythingllm" {...props}></Icon>
