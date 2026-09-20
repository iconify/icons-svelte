<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgkdrkbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgkdrkbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forum-minus-outline" {...props}></Icon>
