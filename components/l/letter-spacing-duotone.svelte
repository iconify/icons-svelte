<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj2t7mbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj2t7mbji primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:letter-spacing-duotone" {...props}></Icon>
