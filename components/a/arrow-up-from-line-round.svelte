<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymcycuvvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymcycuvvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-from-line-round" {...props}></Icon>
