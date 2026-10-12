<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp687lbvu.css';
import '../../css/l/lbcm5baeb.css';
import '../../css/q/q2wkkh6jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hp687lbvu"/><path class="lbcm5baeb"/><path class="q2wkkh6jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:directions-20-bold" {...props}></Icon>
