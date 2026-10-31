<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqcyeib-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqcyeib-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cylinder-fill-round" {...props}></Icon>
