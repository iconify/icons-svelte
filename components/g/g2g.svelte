<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1_9seb6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1_9seb6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:g2g" {...props}></Icon>
