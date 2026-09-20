<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzzm7rb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzzm7rb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-minus" {...props}></Icon>
