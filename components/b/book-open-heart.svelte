<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqch5x_ab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqch5x_ab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-open-heart" {...props}></Icon>
