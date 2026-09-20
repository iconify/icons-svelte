<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhzv6bmss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhzv6bmss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:corona-renderer" {...props}></Icon>
