<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk5u0i5pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zk5u0i5pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ranger-station" {...props}></Icon>
