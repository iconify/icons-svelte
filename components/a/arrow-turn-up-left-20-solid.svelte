<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkwreep6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xkwreep6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-up-left-20-solid" {...props}></Icon>
