<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgca40b7u.css';
import '../../css/n/n10l0kbuj.css';
import '../../css/u/u-3ipjkjd.css';
import '../../css/k/kdauzw8di.css';
import '../../css/s/sq4pxgboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fgca40b7u"/><path class="n10l0kbuj"/><path class="u-3ipjkjd"/><path class="kdauzw8di"/><path class="sq4pxgboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:helicopter-20" {...props}></Icon>
