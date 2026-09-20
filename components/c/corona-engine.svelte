<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewdozj59c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewdozj59c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:corona-engine" {...props}></Icon>
