<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg5oj0bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dg5oj0bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:caret-back" {...props}></Icon>
