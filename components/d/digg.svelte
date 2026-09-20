<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehb6tab-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ehb6tab-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:digg" {...props}></Icon>
