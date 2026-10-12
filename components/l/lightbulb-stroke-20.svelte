<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic8udy9nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ic8udy9nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightbulb-stroke-20" {...props}></Icon>
