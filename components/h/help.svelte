<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1lmytbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1lmytbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:help" {...props}></Icon>
