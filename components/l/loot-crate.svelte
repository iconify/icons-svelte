<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0wc5dbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0wc5dbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:loot-crate" {...props}></Icon>
