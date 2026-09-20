<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en0no1b3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="en0no1b3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-paragraph-spacing" {...props}></Icon>
