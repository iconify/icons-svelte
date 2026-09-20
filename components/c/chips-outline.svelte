<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr2gxdbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qr2gxdbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:chips-outline" {...props}></Icon>
