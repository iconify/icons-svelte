<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqrkjk4za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="eqrkjk4za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:eye-closed" {...props}></Icon>
