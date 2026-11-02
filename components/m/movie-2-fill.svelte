<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au9gtvb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="au9gtvb2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:movie-2-fill" {...props}></Icon>
