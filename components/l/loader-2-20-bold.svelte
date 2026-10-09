<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y06_bibde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y06_bibde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:loader-2-20-bold" {...props}></Icon>
