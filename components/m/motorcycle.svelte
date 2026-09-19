<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdpoi43ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdpoi43ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:motorcycle" {...props}></Icon>
