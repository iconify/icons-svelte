<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1rr9jblv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="z1rr9jblv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hat-cowboy" {...props}></Icon>
