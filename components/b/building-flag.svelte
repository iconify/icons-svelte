<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js926xula.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="js926xula"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:building-flag" {...props}></Icon>
