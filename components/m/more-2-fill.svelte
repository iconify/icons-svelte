<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn6tgc19f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn6tgc19f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-2-fill" {...props}></Icon>
