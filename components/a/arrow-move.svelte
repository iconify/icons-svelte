<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa9x0wb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qa9x0wb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-move" {...props}></Icon>
