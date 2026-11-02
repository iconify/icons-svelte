<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo-0lob9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo-0lob9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-love-line" {...props}></Icon>
