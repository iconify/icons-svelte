<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slwt9gbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="slwt9gbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-football" {...props}></Icon>
