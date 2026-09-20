<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-iyp4zor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h-iyp4zor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flying-saucer" {...props}></Icon>
