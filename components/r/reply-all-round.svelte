<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9u8yg5wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9u8yg5wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:reply-all-round" {...props}></Icon>
