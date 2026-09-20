<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/orab6o7kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="orab6o7kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arkansas" {...props}></Icon>
