<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nin7w1fdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nin7w1fdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:go-first-16" {...props}></Icon>
