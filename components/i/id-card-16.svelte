<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7cvghjjq.css';
import '../../css/x/x9yd_cc7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o7cvghjjq"/><path clip-rule="evenodd" class="x9yd_cc7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:id-card-16" {...props}></Icon>
