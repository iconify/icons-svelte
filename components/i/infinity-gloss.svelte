<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc9g2ibzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc9g2ibzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:infinity-gloss" {...props}></Icon>
