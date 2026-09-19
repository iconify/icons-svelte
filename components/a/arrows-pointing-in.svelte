<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycgy5nb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycgy5nb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrows-pointing-in" {...props}></Icon>
