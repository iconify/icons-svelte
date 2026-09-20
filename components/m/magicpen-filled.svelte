<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0nolhb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0nolhb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:magicpen-filled" {...props}></Icon>
