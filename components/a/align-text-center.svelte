<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf6_ihbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="bf6_ihbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:align-text-center" {...props}></Icon>
