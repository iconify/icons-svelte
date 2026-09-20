<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me46gtb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="me46gtb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:laravel" {...props}></Icon>
