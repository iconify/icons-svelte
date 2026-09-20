<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aahvg3b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aahvg3b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:list-check" {...props}></Icon>
