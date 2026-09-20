<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/as6zalapf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="as6zalapf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ard" {...props}></Icon>
