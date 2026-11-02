<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/behhjsymg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="behhjsymg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:face-line" {...props}></Icon>
