<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv3bkvbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv3bkvbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:clock-two" {...props}></Icon>
