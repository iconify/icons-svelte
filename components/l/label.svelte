<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yt7esm00f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yt7esm00f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:label" {...props}></Icon>
