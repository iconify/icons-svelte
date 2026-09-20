<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1c916b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1c916b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-arrow-down-1-bold" {...props}></Icon>
