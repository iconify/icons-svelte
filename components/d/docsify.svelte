<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv7fy9bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv7fy9bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:docsify" {...props}></Icon>
