<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw5xwqyzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hw5xwqyzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cube-16" {...props}></Icon>
