<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhpqz8y6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhpqz8y6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-check-fill-round" {...props}></Icon>
