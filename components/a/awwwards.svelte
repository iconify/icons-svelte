<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psawn51dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psawn51dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:awwwards" {...props}></Icon>
