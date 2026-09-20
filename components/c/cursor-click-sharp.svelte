<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly1huxb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly1huxb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cursor-click-sharp" {...props}></Icon>
