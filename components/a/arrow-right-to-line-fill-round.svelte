<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7v__r5kb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z7v__r5kb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-right-to-line-fill-round" {...props}></Icon>
