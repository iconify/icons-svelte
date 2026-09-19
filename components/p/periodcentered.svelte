<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dayaw-b9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":77,"height":614};
const content = `<path class="dayaw-b9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:periodcentered" {...props}></Icon>
