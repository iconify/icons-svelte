<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkia4r3ns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkia4r3ns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:ghost-gloss" {...props}></Icon>
