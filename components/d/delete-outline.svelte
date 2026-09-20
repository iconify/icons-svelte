<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2n01eb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2n01eb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-outline" {...props}></Icon>
