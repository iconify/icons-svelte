<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/etwxr4bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="etwxr4bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:hard-hat-check" {...props}></Icon>
