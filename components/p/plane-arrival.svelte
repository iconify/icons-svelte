<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hssc50bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="hssc50bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:plane-arrival" {...props}></Icon>
