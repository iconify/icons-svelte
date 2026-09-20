<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3u3mb96z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3u3mb96z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-alert" {...props}></Icon>
