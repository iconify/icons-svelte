<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdm_ydbbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdm_ydbbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rotate-right-fill-round" {...props}></Icon>
