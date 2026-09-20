<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prb1s5poo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prb1s5poo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-large-line" {...props}></Icon>
