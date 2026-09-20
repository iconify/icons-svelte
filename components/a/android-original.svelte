<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpm6hqb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hpm6hqb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:android-original" {...props}></Icon>
