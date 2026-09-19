<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4-2d34yr.css';
import '../../css/h/hqoymybvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c4-2d34yr"/><path class="hqoymybvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-box-outline" {...props}></Icon>
