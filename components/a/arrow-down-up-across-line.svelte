<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ovedbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="z9ovedbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-down-up-across-line" {...props}></Icon>
