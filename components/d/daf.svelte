<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibke36b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibke36b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:daf" {...props}></Icon>
