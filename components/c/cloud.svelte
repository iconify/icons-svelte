<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8x1f8b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8x1f8b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud" {...props}></Icon>
