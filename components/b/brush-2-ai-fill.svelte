<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrztamb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vrztamb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-2-ai-fill" {...props}></Icon>
