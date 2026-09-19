<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk25przvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1280};
const content = `<path class="yk25przvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:angle-up" {...props}></Icon>
