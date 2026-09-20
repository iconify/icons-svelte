<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0fuz5boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0fuz5boh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:medal-2-fill" {...props}></Icon>
