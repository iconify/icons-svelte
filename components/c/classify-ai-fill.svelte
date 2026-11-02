<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na5768bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na5768bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:classify-ai-fill" {...props}></Icon>
