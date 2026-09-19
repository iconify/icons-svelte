<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1xb_obhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":431,"height":953};
const content = `<path class="l1xb_obhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:dollar" {...props}></Icon>
