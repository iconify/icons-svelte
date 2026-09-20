<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7nn73bmg.css';
import '../../css/u/ukh6i7bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w7nn73bmg"/><path class="ukh6i7bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jaco-dark" {...props}></Icon>
