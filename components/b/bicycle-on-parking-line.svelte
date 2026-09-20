<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyoyubbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vyoyubbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-on-parking-line" {...props}></Icon>
