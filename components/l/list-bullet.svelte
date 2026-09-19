<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1h0t-qkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r1h0t-qkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:list-bullet" {...props}></Icon>
