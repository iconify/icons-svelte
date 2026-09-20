<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2drn0bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2drn0bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:anichart" {...props}></Icon>
