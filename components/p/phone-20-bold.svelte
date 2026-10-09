<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5q5yvb6f.css';
import '../../css/r/rhb8wbjre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o5q5yvb6f"/><path class="rhb8wbjre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-20-bold" {...props}></Icon>
