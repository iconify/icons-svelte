<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3yq0qbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3yq0qbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brush-3-line" {...props}></Icon>
