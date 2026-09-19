<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyozl1h3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":819};
const content = `<path class="yyozl1h3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:percent" {...props}></Icon>
