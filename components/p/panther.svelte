<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjh0hj0uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2016,"height":1984};
const content = `<path class="wjh0hj0uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:panther" {...props}></Icon>
