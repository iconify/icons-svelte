<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7h7y4b-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="u7h7y4b-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:camera-add" {...props}></Icon>
