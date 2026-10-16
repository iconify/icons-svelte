<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o92oj3biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o92oj3biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ocean-acidification-20-bold" {...props}></Icon>
