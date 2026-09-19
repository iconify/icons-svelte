<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez447-bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ez447-bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:o" {...props}></Icon>
