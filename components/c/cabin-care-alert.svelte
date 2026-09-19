<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8_timb4b.css';
import '../../css/n/nqwt54z4d.css';
import '../../css/c/cqy8vydfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c8_timb4b"/><rect class="nqwt54z4d"/><path class="cqy8vydfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:cabin-care-alert" {...props}></Icon>
