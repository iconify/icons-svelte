<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0-o8vb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d0-o8vb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:musical-note-sharp" {...props}></Icon>
