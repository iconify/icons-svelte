<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/julnieboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="julnieboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:repeat-line" {...props}></Icon>
