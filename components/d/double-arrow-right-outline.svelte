<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mol7c5d1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mol7c5d1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:double-arrow-right-outline" {...props}></Icon>
