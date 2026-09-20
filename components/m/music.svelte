<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk4qabbfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk4qabbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:music" {...props}></Icon>
