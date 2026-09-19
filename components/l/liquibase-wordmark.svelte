<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-ujdc4dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c-ujdc4dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:liquibase-wordmark" {...props}></Icon>
