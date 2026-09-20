<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz01e0bkd.css';
import '../../css/m/mmrm4kbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zz01e0bkd"/><path class="mmrm4kbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:building-real-eastate-house-2" {...props}></Icon>
