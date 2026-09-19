<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7dni11kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="v7dni11kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cc-stripe" {...props}></Icon>
