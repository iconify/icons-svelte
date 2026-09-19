<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymgsggb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ymgsggb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bowlingpins" {...props}></Icon>
