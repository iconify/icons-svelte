<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ayo0r2bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ayo0r2bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cash-register" {...props}></Icon>
