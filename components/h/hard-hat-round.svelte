<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n65np6ypu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n65np6ypu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hard-hat-round" {...props}></Icon>
