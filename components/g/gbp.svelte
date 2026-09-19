<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlclwablo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zlclwablo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:gbp" {...props}></Icon>
