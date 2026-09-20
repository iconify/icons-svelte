<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3_9axbeg.css';
import '../../css/d/das08qb6u.css';
import '../../css/w/wlpl3rydx.css';
import '../../css/x/x0ob3uo9t.css';
import '../../css/p/p3-ad7b2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="s3_9axbeg"/><path class="das08qb6u"/><path class="wlpl3rydx"/><path class="x0ob3uo9t"/><path class="p3-ad7b2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:candle" {...props}></Icon>
