<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl3fapb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rl3fapb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:host" {...props}></Icon>
