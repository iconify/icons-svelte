<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpqaeib0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xpqaeib0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:gift-box-1-bold" {...props}></Icon>
