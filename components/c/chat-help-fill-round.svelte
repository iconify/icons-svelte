<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phgq0i6ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="phgq0i6ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-help-fill-round" {...props}></Icon>
