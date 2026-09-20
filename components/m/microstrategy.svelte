<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_4zxf1-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_4zxf1-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:microstrategy" {...props}></Icon>
