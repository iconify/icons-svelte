<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggp6kzb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ggp6kzb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:polis" {...props}></Icon>
