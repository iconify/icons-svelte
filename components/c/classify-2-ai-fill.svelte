<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo-li9bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zo-li9bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-2-ai-fill" {...props}></Icon>
