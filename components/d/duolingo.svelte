<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjum-4nsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjum-4nsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:duolingo" {...props}></Icon>
