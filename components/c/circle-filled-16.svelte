<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmuh9obmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qmuh9obmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:circle-filled-16" {...props}></Icon>
