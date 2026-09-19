<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lypp8ec4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lypp8ec4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:mail-open" {...props}></Icon>
