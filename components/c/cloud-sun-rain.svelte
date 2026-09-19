<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9cy3fv7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="v9cy3fv7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-sun-rain" {...props}></Icon>
