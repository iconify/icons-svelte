<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlb_9o8_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlb_9o8_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:git-merge" {...props}></Icon>
