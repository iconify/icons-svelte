<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl2z-j7sq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bl2z-j7sq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dress-fill" {...props}></Icon>
