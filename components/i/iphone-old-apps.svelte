<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-7y4g4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yx-7y4g4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:iphone-old-apps" {...props}></Icon>
