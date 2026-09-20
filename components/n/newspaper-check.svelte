<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le9dz2kqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le9dz2kqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:newspaper-check" {...props}></Icon>
