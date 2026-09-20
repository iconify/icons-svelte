<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyzmbxboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyzmbxboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-ai-fill" {...props}></Icon>
