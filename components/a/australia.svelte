<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyw3y3bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wyw3y3bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:australia" {...props}></Icon>
