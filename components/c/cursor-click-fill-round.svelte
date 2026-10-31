<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkdep1bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkdep1bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cursor-click-fill-round" {...props}></Icon>
