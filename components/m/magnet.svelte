<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzssdl34u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bzssdl34u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:magnet" {...props}></Icon>
