<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc1e6dbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc1e6dbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:goodreads" {...props}></Icon>
