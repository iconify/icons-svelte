<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hao0u7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hao0u7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:emlakjet" {...props}></Icon>
