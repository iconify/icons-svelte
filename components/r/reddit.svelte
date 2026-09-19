<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hivm86b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="hivm86b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:reddit" {...props}></Icon>
