<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agku-_b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="agku-_b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:image" {...props}></Icon>
