<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk36_pgzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sk36_pgzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-double-diagonal-reverse" {...props}></Icon>
