<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho1q24m-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ho1q24m-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:people-carry-box" {...props}></Icon>
