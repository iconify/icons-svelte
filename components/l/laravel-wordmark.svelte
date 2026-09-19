<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqrder4yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="hqrder4yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:laravel-wordmark" {...props}></Icon>
