<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u02shab-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u02shab-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bluesky-line" {...props}></Icon>
