<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz8h51bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zz8h51bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:leaf" {...props}></Icon>
