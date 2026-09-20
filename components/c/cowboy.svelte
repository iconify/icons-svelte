<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jluaz1kbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jluaz1kbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cowboy" {...props}></Icon>
