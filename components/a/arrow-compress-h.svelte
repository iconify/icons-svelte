<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9-37bbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9-37bbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:arrow-compress-h" {...props}></Icon>
