<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3k87mqng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3k87mqng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-refresh" {...props}></Icon>
