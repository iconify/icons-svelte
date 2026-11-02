<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cedxij8rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cedxij8rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:attachment-3-fill" {...props}></Icon>
