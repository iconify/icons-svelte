<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaw1wpsia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uaw1wpsia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rewind-start-mini-line" {...props}></Icon>
