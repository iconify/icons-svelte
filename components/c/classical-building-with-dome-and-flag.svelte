<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwyxdm3le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hwyxdm3le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:classical-building-with-dome-and-flag" {...props}></Icon>
