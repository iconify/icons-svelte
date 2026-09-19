<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tomm5sbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="tomm5sbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hanukiah" {...props}></Icon>
