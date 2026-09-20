<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_qbg6bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c_qbg6bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:croissant" {...props}></Icon>
