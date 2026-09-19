<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je1i2lqnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="je1i2lqnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-tongue-squint" {...props}></Icon>
