<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1mg6obnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1mg6obnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:myget" {...props}></Icon>
