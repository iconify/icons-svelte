<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urz4zo7ze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urz4zo7ze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:reserved-fill" {...props}></Icon>
