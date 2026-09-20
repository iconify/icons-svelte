<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9pnufbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9pnufbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flip-vertical-2-line" {...props}></Icon>
