<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rny4j3b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":654,"height":1000};
const content = `<path class="rny4j3b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:left-open" {...props}></Icon>
