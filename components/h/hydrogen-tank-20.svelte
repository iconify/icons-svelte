<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yght1vonp.css';
import '../../css/s/s1qzz4b8q.css';
import '../../css/f/fj5yv9btn.css';
import '../../css/o/o9z99rbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yght1vonp"/><path class="s1qzz4b8q"/><path class="fj5yv9btn"/><path class="o9z99rbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-tank-20" {...props}></Icon>
