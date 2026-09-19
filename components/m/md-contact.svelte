<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnu6c421i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dnu6c421i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-contact" {...props}></Icon>
