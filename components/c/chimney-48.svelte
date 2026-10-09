<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwcuq_bqp.css';
import '../../css/y/yb3rr1f2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bwcuq_bqp"/><path class="yb3rr1f2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chimney-48" {...props}></Icon>
