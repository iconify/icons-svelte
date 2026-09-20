<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3ouj08qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ouj08qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:chess-king" {...props}></Icon>
