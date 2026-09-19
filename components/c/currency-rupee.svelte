<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug81a-hsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug81a-hsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:currency-rupee" {...props}></Icon>
