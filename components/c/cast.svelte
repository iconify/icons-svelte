<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fykxwnbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fykxwnbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cast" {...props}></Icon>
