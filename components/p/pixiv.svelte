<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4n378bkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="t4n378bkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:pixiv" {...props}></Icon>
