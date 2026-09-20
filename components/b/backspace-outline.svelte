<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5orvkb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h5orvkb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:backspace-outline" {...props}></Icon>
