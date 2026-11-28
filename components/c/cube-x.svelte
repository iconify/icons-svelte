<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-by9wblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-by9wblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:cube-x" {...props}></Icon>
