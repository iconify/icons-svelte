<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-752u0ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-752u0ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:quote" {...props}></Icon>
