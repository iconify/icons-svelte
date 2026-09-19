<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cimb_3brr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cimb_3brr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:lightning-bolt" {...props}></Icon>
