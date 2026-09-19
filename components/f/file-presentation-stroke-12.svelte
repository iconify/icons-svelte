<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7cpy6-3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t7cpy6-3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-presentation-stroke-12" {...props}></Icon>
