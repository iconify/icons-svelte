<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr8ca4k4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr8ca4k4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:quartz" {...props}></Icon>
