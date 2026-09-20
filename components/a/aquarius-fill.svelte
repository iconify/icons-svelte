<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blim79bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blim79bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aquarius-fill" {...props}></Icon>
