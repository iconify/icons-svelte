<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4npapisz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y4npapisz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-js" {...props}></Icon>
