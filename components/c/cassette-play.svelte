<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atksbtj8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atksbtj8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cassette-play" {...props}></Icon>
