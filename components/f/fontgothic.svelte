<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/weyiv4ekk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="weyiv4ekk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fontgothic" {...props}></Icon>
