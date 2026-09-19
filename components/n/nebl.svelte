<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1m1ux7to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="x1m1ux7to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:nebl" {...props}></Icon>
