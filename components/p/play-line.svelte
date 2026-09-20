<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltxg7rblz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltxg7rblz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:play-line" {...props}></Icon>
