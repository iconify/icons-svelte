<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4y-sm.css';
import '../../css/o/oxmpwq.css';
import '../../css/j/jd_9zf.css';
import '../../css/s/so-from-24.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f4y-sm oxmpwq"/><path class="jd_9zf oxmpwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:facebook" {...props}></Icon>
