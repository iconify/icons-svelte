<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z00ttnbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="z00ttnbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:case-default-16" {...props}></Icon>
