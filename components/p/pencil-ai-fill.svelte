<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x14l441wq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x14l441wq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-ai-fill" {...props}></Icon>
