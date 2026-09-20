<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvfwx8oct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvfwx8oct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gallery-view" {...props}></Icon>
