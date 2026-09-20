<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eutmcdbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eutmcdbok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-2-ai-fill" {...props}></Icon>
