<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxtm55b3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxtm55b3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-info-fill-round" {...props}></Icon>
