<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0tsaxl0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k0tsaxl0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:blockquote-solid" {...props}></Icon>
