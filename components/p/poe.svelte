<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_7jr_bmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="y_7jr_bmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:poe" {...props}></Icon>
