<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8lb625tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="o8lb625tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:github-alt" {...props}></Icon>
