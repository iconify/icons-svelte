<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvkok9nbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvkok9nbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:comment-close-bold" {...props}></Icon>
