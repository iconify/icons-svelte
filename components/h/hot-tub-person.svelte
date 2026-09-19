<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbqo6nbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vbqo6nbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hot-tub-person" {...props}></Icon>
