<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i12dm4t4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i12dm4t4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chevron-up-small" {...props}></Icon>
