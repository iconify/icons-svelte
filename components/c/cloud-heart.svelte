<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctvcq8x9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctvcq8x9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-heart" {...props}></Icon>
