<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epfqiub8e.css';
import '../../css/b/bx-ljfbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="epfqiub8e"/><path class="bx-ljfbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hard-drive-20-bold" {...props}></Icon>
