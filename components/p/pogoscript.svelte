<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w03ix6lll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":286,"height":512};
const content = `<path class="w03ix6lll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:pogoscript" {...props}></Icon>
