<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi1hh1cjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1hh1cjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:passport-gloss" {...props}></Icon>
