<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbnbn7mrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbnbn7mrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:record4-filled" {...props}></Icon>
