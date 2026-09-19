<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkwr-26dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="wkwr-26dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:heading" {...props}></Icon>
