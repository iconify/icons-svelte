<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuwsj3zho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="uuwsj3zho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:folder-closed-stroke-12" {...props}></Icon>
