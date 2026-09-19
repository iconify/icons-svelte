<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzbf6_b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="qzbf6_b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hotel" {...props}></Icon>
