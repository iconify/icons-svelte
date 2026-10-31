<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-cd_q5uv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-cd_q5uv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:checkbox-partial-fill-round" {...props}></Icon>
