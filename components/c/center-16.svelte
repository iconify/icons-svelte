<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqw3nmqqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uqw3nmqqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:center-16" {...props}></Icon>
