<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbt4z81as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbt4z81as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reply-fill" {...props}></Icon>
