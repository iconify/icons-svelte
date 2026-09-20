<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-lk-v-fe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-lk-v-fe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mic-ai-fill" {...props}></Icon>
