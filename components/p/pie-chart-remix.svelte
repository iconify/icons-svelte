<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh6_xb39i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh6_xb39i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pie-chart-remix" {...props}></Icon>
