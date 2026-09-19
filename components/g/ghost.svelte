<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr-75kbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="tr-75kbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ghost" {...props}></Icon>
