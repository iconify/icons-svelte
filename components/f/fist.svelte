<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cidl79b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cidl79b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fist" {...props}></Icon>
