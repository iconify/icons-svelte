<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2uyi9c9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2uyi9c9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:diamond-dot-solid" {...props}></Icon>
