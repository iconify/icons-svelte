<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntohb8g-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntohb8g-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:close-fill" {...props}></Icon>
