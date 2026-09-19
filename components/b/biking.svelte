<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug0q3wbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ug0q3wbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:biking" {...props}></Icon>
