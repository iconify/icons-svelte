<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj-9y3bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="kj-9y3bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:lightbulb" {...props}></Icon>
