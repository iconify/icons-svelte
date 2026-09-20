<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0kl24bxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0kl24bxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rewind-start-mini-fill" {...props}></Icon>
