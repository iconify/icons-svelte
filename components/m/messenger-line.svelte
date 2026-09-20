<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5ok2mboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5ok2mboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:messenger-line" {...props}></Icon>
