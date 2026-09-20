<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvwoswbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvwoswbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:recycle-variant" {...props}></Icon>
