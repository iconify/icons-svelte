<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdg9x3jpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":758,"height":720};
const content = `<path class="mdg9x3jpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ltthon" {...props}></Icon>
