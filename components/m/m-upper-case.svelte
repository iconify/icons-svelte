<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_2gwyvwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="y_2gwyvwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:m-upper-case" {...props}></Icon>
