<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojkk-2kby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ojkk-2kby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-fill-round" {...props}></Icon>
