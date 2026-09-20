<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czbd80bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czbd80bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:rename-light" {...props}></Icon>
