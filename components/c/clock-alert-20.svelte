<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4g3nmxvh.css';
import '../../css/l/lkrm188_r.css';
import '../../css/o/omab5dbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j4g3nmxvh"/><path class="lkrm188_r"/><path class="omab5dbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:clock-alert-20" {...props}></Icon>
