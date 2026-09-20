<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p068o5acv.css';
import '../../css/s/sm2nqnaxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p068o5acv"/><path class="sm2nqnaxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-ai-line" {...props}></Icon>
