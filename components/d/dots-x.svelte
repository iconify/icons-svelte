<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp7wb5b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fp7wb5b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:dots-x" {...props}></Icon>
