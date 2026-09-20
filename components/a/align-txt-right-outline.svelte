<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1m0fhbyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m1m0fhbyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:align-txt-right-outline" {...props}></Icon>
