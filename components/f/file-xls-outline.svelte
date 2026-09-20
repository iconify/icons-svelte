<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrd_c7u5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vrd_c7u5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-xls-outline" {...props}></Icon>
