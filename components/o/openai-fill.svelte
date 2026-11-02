<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b33gvabus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b33gvabus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:openai-fill" {...props}></Icon>
