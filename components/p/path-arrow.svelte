<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6lm97i8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6lm97i8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:path-arrow" {...props}></Icon>
