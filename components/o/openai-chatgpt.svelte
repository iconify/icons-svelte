<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znd_geczm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znd_geczm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openai-chatgpt" {...props}></Icon>
