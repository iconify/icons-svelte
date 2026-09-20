<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js6s8rg9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="js6s8rg9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:replit" {...props}></Icon>
