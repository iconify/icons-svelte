<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm2l9yb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm2l9yb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:haze-2-fill" {...props}></Icon>
