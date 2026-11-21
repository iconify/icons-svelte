<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_6t34bzh.css';
import '../../css/x/x-ff3h11f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d_6t34bzh"/><circle class="x-ff3h11f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:alert" {...props}></Icon>
