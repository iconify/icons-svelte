<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk7-0nbwz.css';
import '../../css/l/lyrbudsuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="fk7-0nbwz"/><path class="lyrbudsuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:road" {...props}></Icon>
