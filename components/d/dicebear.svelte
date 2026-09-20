<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbx-v0bcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gbx-v0bcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:dicebear" {...props}></Icon>
