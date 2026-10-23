<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwh8_mg-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwh8_mg-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:post-comments" {...props}></Icon>
