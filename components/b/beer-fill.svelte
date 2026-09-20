<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_s_c5kte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_s_c5kte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:beer-fill" {...props}></Icon>
