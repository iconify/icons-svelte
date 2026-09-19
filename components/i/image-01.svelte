<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkc0vy_ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkc0vy_ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:image-01" {...props}></Icon>
