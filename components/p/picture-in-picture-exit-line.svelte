<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8w9k1b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8w9k1b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:picture-in-picture-exit-line" {...props}></Icon>
