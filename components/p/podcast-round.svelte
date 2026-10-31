<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpj8x5bzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpj8x5bzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:podcast-round" {...props}></Icon>
