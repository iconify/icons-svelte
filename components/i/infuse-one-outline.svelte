<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oud75tbup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oud75tbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:infuse-one-outline" {...props}></Icon>
