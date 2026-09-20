<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm_kdvb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qm_kdvb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-barrier" {...props}></Icon>
