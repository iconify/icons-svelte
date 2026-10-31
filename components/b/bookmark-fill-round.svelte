<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k09r7yb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k09r7yb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bookmark-fill-round" {...props}></Icon>
