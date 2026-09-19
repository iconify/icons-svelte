<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt8tbghbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rt8tbghbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:bar-right" {...props}></Icon>
