<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_p5yv07v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_p5yv07v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hard-hat-fill-round" {...props}></Icon>
